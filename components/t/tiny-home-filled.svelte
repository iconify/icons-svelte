<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf4l17ywk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf4l17ywk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tiny-home-filled" {...props}></Icon>
