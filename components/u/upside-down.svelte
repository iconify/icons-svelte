<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqbkv8u2i.css';
import '../../css/a/a-nr90z_g.css';
import '../../css/i/ikrkupm8l.css';
import '../../css/o/ockxf75_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="a-nr90z_g"/><circle class="ikrkupm8l"/><circle class="ockxf75_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:upside-down" {...props}></Icon>
