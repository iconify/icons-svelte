<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doj9dq_jg.css';
import '../../css/e/ehv3lsbxi.css';
import '../../css/h/hb8m0waiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="doj9dq_jg"><path class="ehv3lsbxi"/><path class="hb8m0waiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:zzz" {...props}></Icon>
