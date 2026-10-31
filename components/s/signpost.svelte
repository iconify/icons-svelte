<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/d-pgtlbgj.css';
import '../../css/v/vspil-doj.css';
import '../../css/s/som12ybho.css';
import '../../css/v/v53h7w87j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="d-pgtlbgj wm-shadow"/><path class="vspil-doj"/><path class="som12ybho"/><path class="v53h7w87j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:signpost" {...props}></Icon>
