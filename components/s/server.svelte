<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wobsqr1mq.css';
import '../../css/p/pw90w5qlp.css';
import '../../css/c/cwa6rzb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wobsqr1mq"/><path class="pw90w5qlp"/><path class="cwa6rzb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:server" {...props}></Icon>
