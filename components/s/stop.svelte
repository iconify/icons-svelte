<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8-oes8zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c8-oes8zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stop" {...props}></Icon>
