<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-9xdinh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jt-9xdinh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:soup" {...props}></Icon>
