<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcg46tb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fcg46tb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-xmark" {...props}></Icon>
