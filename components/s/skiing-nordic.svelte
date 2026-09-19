<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5bo1pb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="v5bo1pb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:skiing-nordic" {...props}></Icon>
