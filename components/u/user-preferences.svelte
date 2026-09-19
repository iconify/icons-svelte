<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7sr6ubzr.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/z/z-d7g1b-g.css';
import '../../css/h/hclqxqegg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><g class="d2kvgvbvc"><path class="z-d7g1b-g"/><path class="hclqxqegg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:user-preferences" {...props}></Icon>
