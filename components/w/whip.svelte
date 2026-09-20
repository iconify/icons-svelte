<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ydws45o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="b2ydws45o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:whip" {...props}></Icon>
