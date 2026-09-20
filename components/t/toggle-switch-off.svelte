<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h68vtmp3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h68vtmp3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:toggle-switch-off" {...props}></Icon>
