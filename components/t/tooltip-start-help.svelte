<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb9h84b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bb9h84b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-start-help" {...props}></Icon>
