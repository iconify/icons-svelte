<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inc6vt4-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inc6vt4-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:subscriptions-sharp" {...props}></Icon>
