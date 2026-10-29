<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/e/egwfombsu.css';
import '../../css/h/hbl9yebar.css';
import '../../css/d/duo2k8-5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="egwfombsu"/><path class="hbl9yebar"/><path class="duo2k8-5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:wink" {...props}></Icon>
