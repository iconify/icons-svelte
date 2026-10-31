<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg9redb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg9redb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-code-fill-round" {...props}></Icon>
