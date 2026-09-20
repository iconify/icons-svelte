<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj5w7lbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5w7lbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:trending-up" {...props}></Icon>
