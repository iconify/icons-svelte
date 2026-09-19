<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0g1ggb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0g1ggb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:your-spotify" {...props}></Icon>
