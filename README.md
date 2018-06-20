### 批量update

  session.query(News).filter(News.tid==0).update({News.tid:100})
  session.commit()