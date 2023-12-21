<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="bdb98bfd-3423-46f3-a2ec-3b6cba0f1a5e"
    v-bind:style="{'width':'100%','height':'auto'}">
    <WBadge href="" color="#FFFFFF" v-bind:exact="false" v-bind:active="false" v-bind:append="false" v-bind:rotate="0"
      caption="Badge" variant="secondary" v-bind:disabled="false" linkTarget="_top" ncLinkType="link" tagOfBadge="a"
      v-bind:pillOfBadge="false" animationName="" ncTooltipText=""
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'caption','displayName':'Caption'}]}"
      toForRouterLink="to" ncClickFontColor="#0000FF" ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000"
      ncDisableFontColor="#4285f4" position="relative" id="5bc910fd-188e-4c54-9e4f-7a0a67f79354"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Roboto','fontWeight':400,'lineHeight':'1.25','marginLeft':'0px','paddingTop':'5px','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','marginRight':'0px','paddingLeft':'5px','wordSpacing':'0px','marginBottom':'0px','mixBlendMode':'normal','paddingRight':'5px','letterSpacing':'0px','paddingBottom':'5px','textTransform':'none','backdropFilter':'none','textDecoration':'none','zIndex':2}"/>
    <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
      color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="primary"
      ncBgType="bgColor" v-bind:isEnabled="true" background="#007bff" linkTarget="_top" ncLinkType="link"
      borderColor="#007bff" v-bind:resetTrigger="false" animationName="" ncTooltipText="" verticalWidth="60px"
      formTransition="none"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
      horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
      nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
      ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
      ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
      position="relative" id="3d32d45d-a6be-401d-90ea-f7ff0f78360c"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'','paddingLeft':'','wordSpacing':'0px','marginBottom':'','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':3}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@import 'src/assets/styles/scroll';
 @include custom-scroll();
@media (min-width: 1024.05px){
[id='bdb98bfd-3423-46f3-a2ec-3b6cba0f1a5e'] {
             display: grid; 
             grid-template-columns: 31.5234375rem 5.3125rem 8.671875rem 4.296875rem 50.1953125rem;
             grid-template-rows: minmax(23.125rem, max-content) minmax(0.9375rem, max-content) minmax(1.328125rem, max-content) minmax(1.09375rem, max-content) minmax(29.765625rem, max-content);
          }
[id='5bc910fd-188e-4c54-9e4f-7a0a67f79354']{
          grid-area: 2/4/4/5;
          font-size: Max(Min(15rem, 12px),1.171875rem);
          }
[id='3d32d45d-a6be-401d-90ea-f7ff0f78360c']{
          grid-area: 3/2/5/3;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='bdb98bfd-3423-46f3-a2ec-3b6cba0f1a5e'] {
             display: grid; 
             grid-template-columns: 38.57421875rem 6.640625rem 10.83984375rem 5.37109375rem 38.57421875rem;
             grid-template-rows: minmax(28.90625rem, max-content) minmax(1.171875rem, max-content) minmax(1.66015625rem, max-content) minmax(1.3671875rem, max-content) minmax(3.125rem, max-content);
          }
[id='5bc910fd-188e-4c54-9e4f-7a0a67f79354']{
          grid-area: 2/4/4/5;
          font-size: Max(Min(15rem, 12px),1.46484375rem);
          }
[id='3d32d45d-a6be-401d-90ea-f7ff0f78360c']{
          grid-area: 3/2/5/3;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='bdb98bfd-3423-46f3-a2ec-3b6cba0f1a5e'] {
             display: grid; 
             grid-template-columns: 34.765625rem 8.854166666666666rem 14.453125rem 7.161458333333333rem 34.765625rem;
             grid-template-rows: minmax(38.541666666666664rem, max-content) minmax(1.5625rem, max-content) minmax(2.2135416666666665rem, max-content) minmax(1.8229166666666667rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='5bc910fd-188e-4c54-9e4f-7a0a67f79354']{
          grid-area: 2/4/4/5;
          font-size: Max(Min(15rem, 12px),1.953125rem);
          }
[id='3d32d45d-a6be-401d-90ea-f7ff0f78360c']{
          grid-area: 3/2/5/3;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='bdb98bfd-3423-46f3-a2ec-3b6cba0f1a5e'] {
             display: grid; 
             grid-template-columns: 25.625rem 14.166666666666666rem 23.125rem 11.458333333333334rem 25.625rem;
             grid-template-rows: minmax(61.666666666666664rem, max-content) minmax(2.5rem, max-content) minmax(3.5416666666666665rem, max-content) minmax(2.9166666666666665rem, max-content) minmax(5rem, max-content);
          }
[id='5bc910fd-188e-4c54-9e4f-7a0a67f79354']{
          grid-area: 2/4/4/5;
          font-size: Max(Min(15rem, 12px),3.125rem);
          }
[id='3d32d45d-a6be-401d-90ea-f7ff0f78360c']{
          grid-area: 3/2/5/3;
          font-size: Max(Min(12rem, 12px),2.5rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='bdb98bfd-3423-46f3-a2ec-3b6cba0f1a5e'] {
             display: grid; 
             grid-template-columns: 40.93333333333334rem 1.7333333333333334rem 14.666666666666666rem 1.7333333333333325rem 40.93333333333334rem;
             grid-template-rows: minmax(78.93333333333334rem, max-content) minmax(8.266666666666666rem, max-content) minmax(6.4rem, max-content) minmax(7.733333333333333rem, max-content) minmax(6.4rem, max-content);
          }
[id='5bc910fd-188e-4c54-9e4f-7a0a67f79354']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(15rem, 12px),4rem);
          }
[id='3d32d45d-a6be-401d-90ea-f7ff0f78360c']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),3.2rem);
          }
}
</style>