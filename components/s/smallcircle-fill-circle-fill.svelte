<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6w734d5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f6w734d5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:smallcircle-fill-circle-fill" {...props}></Icon>
