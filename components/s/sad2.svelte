<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1c4z18tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p1c4z18tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sad2" {...props}></Icon>
