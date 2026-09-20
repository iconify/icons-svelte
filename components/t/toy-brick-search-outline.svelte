<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6r397xvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6r397xvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-search-outline" {...props}></Icon>
