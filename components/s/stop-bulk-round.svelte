<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9g8vnx-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9g8vnx-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stop-bulk-round" {...props}></Icon>
