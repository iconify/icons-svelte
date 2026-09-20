<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boxar-4qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="boxar-4qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wmo4680-86" {...props}></Icon>
