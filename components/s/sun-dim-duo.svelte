<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ab_9pivlh.css';
import '../../css/q/q42xo2b2p.css';
import '../../css/b/bk04fhbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ab_9pivlh"/><path class="q42xo2b2p wm-a"/><path class="bk04fhbuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sun-dim-duo" {...props}></Icon>
