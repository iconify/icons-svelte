<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb0jcv6dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb0jcv6dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:wind" {...props}></Icon>
