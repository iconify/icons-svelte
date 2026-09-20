<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ityz56bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ityz56bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:thermometer-internal" {...props}></Icon>
