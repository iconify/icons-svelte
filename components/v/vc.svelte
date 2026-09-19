<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/k/ksyn4cb8f.css';
import '../../css/q/qz9-edcvr.css';
import '../../css/g/grssl4u2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="ksyn4cb8f"/><path class="qz9-edcvr"/><path class="grssl4u2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:vc" {...props}></Icon>
