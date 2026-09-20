<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gomhksbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gomhksbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-door-vertical" {...props}></Icon>
