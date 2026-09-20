<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/djqetsxsa.css';
import '../../css/c/c7vp9yj-i.css';
import '../../css/y/ymn18bcnu.css';
import '../../css/l/l5_v93xsj.css';
import '../../css/d/djr3_db2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="djqetsxsa"/><path class="c7vp9yj-i"/><path class="ymn18bcnu"/><path clip-rule="evenodd" class="l5_v93xsj"/><path clip-rule="evenodd" class="djr3_db2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:tauri-light" {...props}></Icon>
