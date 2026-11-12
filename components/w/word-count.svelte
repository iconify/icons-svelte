<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2qr42b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2qr42b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:word-count" {...props}></Icon>
