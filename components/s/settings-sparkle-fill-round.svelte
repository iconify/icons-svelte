<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r602s8bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r602s8bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:settings-sparkle-fill-round" {...props}></Icon>
