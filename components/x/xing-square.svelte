<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5ibdneby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="u5ibdneby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:xing-square" {...props}></Icon>
