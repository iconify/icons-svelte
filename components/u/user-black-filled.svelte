<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ozg169z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j5ozg169z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-black-filled" {...props}></Icon>
