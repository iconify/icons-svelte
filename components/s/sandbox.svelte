<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkxvm8-6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wkxvm8-6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:sandbox" {...props}></Icon>
