<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/a/ayrm58b3o.css';
import '../../css/m/mfzbs70ff.css';
import '../../css/n/n4cyhmbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="ayrm58b3o"/><path class="mfzbs70ff"/><path class="n4cyhmbkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:ru-ud" {...props}></Icon>
