<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9-nrmbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c9-nrmbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rss-16" {...props}></Icon>
