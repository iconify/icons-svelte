<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7rzdrb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7rzdrb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-price-outline" {...props}></Icon>
