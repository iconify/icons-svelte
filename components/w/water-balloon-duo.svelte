<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i-4h2ab-f.css';
import '../../css/k/kfb2hf1uo.css';
import '../../css/p/pfunrccay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i-4h2ab-f"/><path class="kfb2hf1uo wm-a"/><path class="pfunrccay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:water-balloon-duo" {...props}></Icon>
