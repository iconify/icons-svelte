<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l1s8gobzn.css';
import '../../css/b/b86buo32x.css';
import '../../css/k/ki55z6ilg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l1s8gobzn wm-a"/><path class="b86buo32x"/><path class="ki55z6ilg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:unlock" {...props}></Icon>
