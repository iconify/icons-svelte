<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twmqo33gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="twmqo33gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:swimming-pool" {...props}></Icon>
