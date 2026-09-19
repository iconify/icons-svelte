<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9gk6b6yh.css';
import '../../css/v/vfp8vn0fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g9gk6b6yh"/><path class="vfp8vn0fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-whatsapp-outline" {...props}></Icon>
