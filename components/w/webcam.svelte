<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxkre9b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="bxkre9b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:webcam" {...props}></Icon>
