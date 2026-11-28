<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c843pkykg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x11pprywc.css';
import '../../css/v/vcp9f7b5e.css';
import '../../css/z/z2r0njj4k.css';
import '../../css/h/htzsep-dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c843pkykg secondary"/><g class="dt0cm9dhy primary"><path class="x11pprywc"/><path class="vcp9f7b5e"/><path class="z2r0njj4k"/><path class="htzsep-dn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:skateboard-duo" {...props}></Icon>
