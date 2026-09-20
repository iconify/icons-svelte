<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8v-pb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yg8v-pb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:scaffold" {...props}></Icon>
