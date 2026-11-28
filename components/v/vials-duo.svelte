<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d13g_obly.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p8zug3oqg.css';
import '../../css/p/p-hb2dbpu.css';
import '../../css/z/zl93bsbqp.css';
import '../../css/k/krynnrlat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d13g_obly secondary"/><g class="dt0cm9dhy primary"><path class="p8zug3oqg"/><path class="p-hb2dbpu"/><path class="zl93bsbqp"/><path class="krynnrlat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vials-duo" {...props}></Icon>
