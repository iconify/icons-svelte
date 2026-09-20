<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_bxzvurr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="o_bxzvurr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:sunset" {...props}></Icon>
