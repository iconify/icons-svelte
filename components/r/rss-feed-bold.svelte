<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsq76_m7h.css';
import '../../css/g/ge4x6hrjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsq76_m7h"/><path class="ge4x6hrjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:rss-feed-bold" {...props}></Icon>
