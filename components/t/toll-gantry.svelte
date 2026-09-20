<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju0-6kfns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ju0-6kfns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:toll-gantry" {...props}></Icon>
