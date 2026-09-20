<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtnihcb_h.css';
import '../../css/l/lgq_fxbzk.css';
import '../../css/p/p9ptc-gsx.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/j0pbotpte.css';
import '../../css/l/lcq5ssbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qtnihcb_h"/><path class="lgq_fxbzk"/><path class="p9ptc-gsx"/><g class="jn8qy4bru"><path class="j0pbotpte"/><path class="lcq5ssbsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:scroll" {...props}></Icon>
