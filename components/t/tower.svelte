<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx0x-mbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bx0x-mbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tower" {...props}></Icon>
