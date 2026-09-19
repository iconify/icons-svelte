<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/nnfv0rblz.css';
import '../../css/h/hu8xoqe3o.css';
import '../../css/z/zwtof6bxy.css';
import '../../css/s/sax84bbdt.css';
import '../../css/a/aiakpdbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="nnfv0rblz"/><circle class="hu8xoqe3o"/><circle class="zwtof6bxy"/><path class="sax84bbdt"/><path class="aiakpdbbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:us-sc" {...props}></Icon>
