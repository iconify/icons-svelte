<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rygkx9byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rygkx9byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vacuum-cleaner" {...props}></Icon>
