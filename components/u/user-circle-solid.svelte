<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx1tun3fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx1tun3fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-circle-solid" {...props}></Icon>
