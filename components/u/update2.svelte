<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reaqlzbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="reaqlzbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:update2" {...props}></Icon>
