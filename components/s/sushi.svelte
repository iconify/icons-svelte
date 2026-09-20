<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6wah6j7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b6wah6j7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sushi" {...props}></Icon>
