<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw_oclbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aw_oclbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:rss" {...props}></Icon>
