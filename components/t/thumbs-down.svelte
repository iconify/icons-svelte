<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zujyr9_da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zujyr9_da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:thumbs-down" {...props}></Icon>
