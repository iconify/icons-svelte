<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z9h-83bpq.css';
import '../../css/a/adf1zybll.css';
import '../../css/n/nfk5u5bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z9h-83bpq"/><path class="adf1zybll"/><path class="nfk5u5bfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:separator-horizontal" {...props}></Icon>
