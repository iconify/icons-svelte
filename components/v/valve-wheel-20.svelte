<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6sb2hngk.css';
import '../../css/h/hvcttkn8s.css';
import '../../css/q/qtozcib7o.css';
import '../../css/w/wyzn1emnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n6sb2hngk"/><path class="hvcttkn8s"/><path class="qtozcib7o"/><path class="wyzn1emnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:valve-wheel-20" {...props}></Icon>
