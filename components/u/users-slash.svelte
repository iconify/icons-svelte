<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3l31-4do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b3l31-4do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users-slash" {...props}></Icon>
