<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhu7n8bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bhu7n8bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:trash-arrow-up" {...props}></Icon>
