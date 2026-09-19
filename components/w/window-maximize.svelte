<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j62jmlv1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="j62jmlv1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:window-maximize" {...props}></Icon>
