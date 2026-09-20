<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjvs1cblk.css';
import '../../css/i/i81te_6rg.css';
import '../../css/u/u29l2rupw.css';
import '../../css/a/a_cxysblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="mjvs1cblk"/><path class="i81te_6rg"/><path class="u29l2rupw"/><path class="a_cxysblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:unlocked" {...props}></Icon>
