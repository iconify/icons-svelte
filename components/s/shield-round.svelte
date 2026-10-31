<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whr5k5f0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whr5k5f0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-round" {...props}></Icon>
