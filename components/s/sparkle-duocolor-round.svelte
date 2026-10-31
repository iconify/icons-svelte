<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmqyipb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmqyipb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sparkle-duocolor-round" {...props}></Icon>
