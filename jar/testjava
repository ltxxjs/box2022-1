package com.github.catvod.spider;

import android.content.Context;
import com.github.catvod.crawler.Spider;
import com.github.catvod.spider.merge.QH;
import com.github.catvod.spider.merge.RNp;
import com.github.catvod.spider.merge.w9.h;
import java.util.HashMap;
import java.util.Iterator;
import java.util.List;
import okhttp3.Call;
import org.json.JSONArray;
import org.json.JSONException;
import org.json.JSONObject;

public class Alist
  extends Spider
{
  private JSONObject m;
  
  public String categoryContent(final String paramString1, String paramString2, boolean paramBoolean, HashMap<String, String> paramHashMap)
  {
    try
    {
      int i = paramString1.indexOf('$');
      String str1 = paramString1.substring(0, i);
      String str2 = paramString1.substring(i + 1);
      StringBuilder localStringBuilder = new StringBuilder();
      localStringBuilder.append(this.m.getString(str1));
      localStringBuilder.append(RNp.d("472D3D0B69151D2E210B254A182D390A"));
      String str3 = localStringBuilder.toString();
      JSONObject localJSONObject1 = new JSONObject();
      localJSONObject1.put(RNp.d("182D390A"), str2);
      final JSONArray localJSONArray = new JSONArray();
      QH.l(QH.cJ(), str3, localJSONObject1.toString(), new w9.h()
      {
        protected void onFailure(Call paramAnonymousCall, Exception paramAnonymousException) {}
        
        protected void onResponse(String paramAnonymousString)
        {
          String str1 = RNp.d("1B253707");
          String str2 = RNp.d("062D2007");
          try
          {
            JSONArray localJSONArray = new JSONObject(paramAnonymousString).getJSONObject(RNp.d("0C2D3903")).getJSONArray(RNp.d("0E25210735"));
            for (int i = 0; i < localJSONArray.length(); i++)
            {
              JSONObject localJSONObject1 = localJSONArray.getJSONObject(i);
              String str3 = localJSONObject1.getString(RNp.d("1C24380F240B092521"));
              boolean bool = str3.isEmpty();
              String str4 = RNp.d("1C353D07");
              if ((bool) && (localJSONObject1.getInt(str4) == 1)) {
                str3 = RNp.d("003839127C4A47252005774B5B3C23056806072162507E540D7E755627535F7C755473045F7D295B77505979755470505D7E2F5720545F7E2F4C360B0F");
              }
              JSONObject localJSONObject2 = new JSONObject();
              String str5 = RNp.d("1E23293D2F01");
              StringBuilder localStringBuilder1 = new StringBuilder();
              localStringBuilder1.append(paramString1);
              String str6 = paramString1;
              int j = str6.charAt(str6.length() - 1);
              String str7 = "";
              String str8;
              if (j == 47) {
                str8 = str7;
              } else {
                str8 = RNp.d("47");
              }
              localStringBuilder1.append(str8);
              localStringBuilder1.append(localJSONObject1.getString(str2));
              localJSONObject2.put(str5, localStringBuilder1.toString());
              localJSONObject2.put(RNp.d("1E23293D28040529"), localJSONObject1.getString(str2));
              localJSONObject2.put(RNp.d("1E23293D360C0B"), str3);
              String str9 = RNp.d("1E23293D32040F");
              String str10;
              if (localJSONObject1.getInt(str4) == 1) {
                str10 = RNp.d("0E2321062317");
              } else {
                str10 = RNp.d("0E252107");
              }
              localJSONObject2.put(str9, str10);
              long l = localJSONObject1.getLong(str1);
              double d1 = l;
              double d2;
              String str11;
              if (d1 > 1099511627776.0D)
              {
                Double.isNaN(d1);
                d2 = d1 / 1099511627776.0D;
                str11 = RNp.d("3C0E");
              }
              else if (d1 > 1073741824.0D)
              {
                Double.isNaN(d1);
                d2 = d1 / 1073741824.0D;
                str11 = RNp.d("2F0E");
              }
              else if (d1 > 1048576.0D)
              {
                Double.isNaN(d1);
                d2 = d1 / 1048576.0D;
                str11 = RNp.d("250E");
              }
              else
              {
                Double.isNaN(d1);
                d2 = d1 / 1024.0D;
                str11 = RNp.d("230E");
              }
              if (localJSONObject1.getLong(str1) != 0L)
              {
                String str13 = RNp.d("4D627F046316");
                Object[] arrayOfObject = new Object[2];
                arrayOfObject[0] = Double.valueOf(d2);
                arrayOfObject[1] = str11;
                str7 = String.format(str13, arrayOfObject);
              }
              String str12 = RNp.d("1E23293D3400052D3F0935");
              if (localJSONObject1.getInt(str4) == 1)
              {
                StringBuilder localStringBuilder2 = new StringBuilder();
                localStringBuilder2.append(str7);
                localStringBuilder2.append(RNp.d("48AADBE5A2DEDEA9E9DB"));
                str7 = localStringBuilder2.toString();
              }
              localJSONObject2.put(str12, str7);
              localJSONArray.put(localJSONObject2);
            }
            return;
          }
          catch (Exception localException)
          {
            localException.printStackTrace();
          }
        }
      });
      JSONObject localJSONObject2 = new JSONObject();
      localJSONObject2.put(RNp.d("182D2A07"), 1);
      localJSONObject2.put(RNp.d("182D2A07250A1D2239"), 1);
      localJSONObject2.put(RNp.d("0425200B32"), localJSONArray.length());
      localJSONObject2.put(RNp.d("1C2339032A"), localJSONArray.length());
      localJSONObject2.put(RNp.d("04253E16"), localJSONArray);
      String str4 = localJSONObject2.toString();
      return str4;
    }
    catch (Exception localException)
    {
      localException.printStackTrace();
    }
    return "";
  }
  
  public String detailContent(List<String> paramList)
  {
    try
    {
      final String str1 = (String)paramList.get(0);
      int i = str1.indexOf('$');
      String str2 = str1.substring(0, i);
      String str3 = str1.substring(i + 1);
      StringBuilder localStringBuilder = new StringBuilder();
      localStringBuilder.append(this.m.getString(str2));
      localStringBuilder.append(RNp.d("472D3D0B69151D2E210B254A182D390A"));
      String str4 = localStringBuilder.toString();
      JSONObject localJSONObject1 = new JSONObject();
      localJSONObject1.put(RNp.d("182D390A"), str3);
      JSONObject localJSONObject2 = new JSONObject();
      final JSONArray localJSONArray = new JSONArray();
      QH.l(QH.cJ(), str4, localJSONObject1.toString(), new w9.h()
      {
        protected void onFailure(Call paramAnonymousCall, Exception paramAnonymousException) {}
        
        protected void onResponse(String paramAnonymousString)
        {
          String str1 = RNp.d("062D2007");
          try
          {
            JSONArray localJSONArray = new JSONObject(paramAnonymousString).getJSONObject(RNp.d("0C2D3903")).getJSONArray(RNp.d("0E25210735"));
            for (int i = 0; i < localJSONArray.length(); i++)
            {
              JSONObject localJSONObject1 = localJSONArray.getJSONObject(i);
              String str2 = localJSONObject1.getString(RNp.d("1D3E21"));
              if (str2.indexOf(RNp.d("4763")) == 0)
              {
                StringBuilder localStringBuilder1 = new StringBuilder();
                localStringBuilder1.append(RNp.d("003839127C"));
                localStringBuilder1.append(str2);
                str2 = localStringBuilder1.toString();
              }
              JSONObject localJSONObject2 = new JSONObject();
              String str3 = RNp.d("1E23293D2F01");
              StringBuilder localStringBuilder2 = new StringBuilder();
              localStringBuilder2.append(str1);
              localStringBuilder2.append(RNp.d("47"));
              localStringBuilder2.append(localJSONObject1.getString(str1));
              localJSONObject2.put(str3, localStringBuilder2.toString());
              localJSONObject2.put(RNp.d("1E23293D28040529"), localJSONObject1.getString(str1));
              localJSONObject2.put(RNp.d("1E23293D360C0B"), localJSONObject1.getString(RNp.d("1C24380F240B092521")));
              String str4 = RNp.d("1E23293D32040F");
              String str5;
              if (localJSONObject1.getInt(RNp.d("1C353D07")) == 1) {
                str5 = RNp.d("0E2321062317");
              } else {
                str5 = RNp.d("0E252107");
              }
              localJSONObject2.put(str4, str5);
              localJSONObject2.put(RNp.d("1E23293D360909351204340A05"), RNp.d("8EDEE084D2DB"));
              String str6 = RNp.d("1E23293D3609093512173409");
              StringBuilder localStringBuilder3 = new StringBuilder();
              localStringBuilder3.append(localJSONObject1.getString(str1));
              localStringBuilder3.append(RNp.d("4C"));
              localStringBuilder3.append(str2);
              localJSONObject2.put(str6, localStringBuilder3.toString());
              localJSONArray.put(localJSONObject2);
            }
            return;
          }
          catch (Exception localException)
          {
            localException.printStackTrace();
          }
        }
      });
      localJSONObject2.put(RNp.d("04253E16"), localJSONArray);
      String str5 = localJSONObject2.toString();
      return str5;
    }
    catch (Exception localException)
    {
      localException.printStackTrace();
    }
    return "";
  }
  
  public String homeContent(boolean paramBoolean)
  {
    try
    {
      JSONArray localJSONArray = new JSONArray();
      Iterator localIterator = this.m.keys();
      while (localIterator.hasNext())
      {
        String str2 = (String)localIterator.next();
        this.m.getString(str2);
        JSONObject localJSONObject2 = new JSONObject();
        String str3 = RNp.d("1C353D07190C0C");
        StringBuilder localStringBuilder = new StringBuilder();
        localStringBuilder.append(str2);
        localStringBuilder.append(RNp.d("4C63"));
        localJSONObject2.put(str3, localStringBuilder.toString());
        localJSONObject2.put(RNp.d("1C353D07190B092128"), str2);
        localJSONObject2.put(RNp.d("1C353D071903042D2A"), RNp.d("59"));
        localJSONArray.put(localJSONObject2);
      }
      new JSONArray();
      JSONObject localJSONObject1 = new JSONObject();
      localJSONObject1.put(RNp.d("0B202C1135"), localJSONArray);
      if (paramBoolean) {
        localJSONObject1.put(RNp.d("0E25211623171B"), new JSONObject(RNp.d("1331")));
      }
      String str1 = localJSONObject1.toString();
      return str1;
    }
    catch (Exception localException)
    {
      localException.printStackTrace();
    }
    return "";
  }
  
  public void init(Context paramContext, String paramString)
  {
    m(this, paramContext);
    this.m = new JSONObject();
    try
    {
      String[] arrayOfString1 = paramString.split(RNp.d("4B"));
      for (int i = 0; i < arrayOfString1.length; i++)
      {
        String[] arrayOfString2 = arrayOfString1[i].split(RNp.d("3468"));
        if (arrayOfString2.length == 1) {
          this.m.put(RNp.d("0920241132"), arrayOfString2[0]);
        } else if (arrayOfString2.length == 2) {
          this.m.put(arrayOfString2[0], arrayOfString2[1]);
        }
      }
      return;
    }
    catch (JSONException localJSONException)
    {
      localJSONException.printStackTrace();
    }
  }
  
  public String playerContent(String paramString1, String paramString2, List<String> paramList)
  {
    try
    {
      JSONObject localJSONObject = new JSONObject();
      localJSONObject.put(RNp.d("182D3F1123"), 0);
      localJSONObject.put(RNp.d("18202C1B131704"), "");
      localJSONObject.put(RNp.d("1D3E21"), paramString2);
      String str = localJSONObject.toString();
      return str;
    }
    catch (Exception localException)
    {
      localException.printStackTrace();
    }
    return "";
  }
  
  public String searchContent(String paramString, boolean paramBoolean)
  {
    return "";
  }
}
