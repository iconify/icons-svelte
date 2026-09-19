<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/y/yfvu-jbye.css';
import '../../css/f/fg2nprquv.css';
import '../../css/o/ow7ybdcjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="yfvu-jbye"/><path class="fg2nprquv"/><path class="ow7ybdcjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:tt" {...props}></Icon>
