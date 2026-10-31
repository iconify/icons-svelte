<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eivnb-q9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eivnb-q9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-none-duotone-round" {...props}></Icon>
