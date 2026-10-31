<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikp4edbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikp4edbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trending-up-duotone-round" {...props}></Icon>
