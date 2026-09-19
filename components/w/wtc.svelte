<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/am_qhhbci.css';
import '../../css/h/h7p8jpp_k.css';
import '../../css/o/osu72-hwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="am_qhhbci"/><path class="h7p8jpp_k"/><path class="osu72-hwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:wtc" {...props}></Icon>
