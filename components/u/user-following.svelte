<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-o_vwbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p-o_vwbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:user-following" {...props}></Icon>
