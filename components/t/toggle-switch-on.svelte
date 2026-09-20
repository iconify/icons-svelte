<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1-r7x1oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="f1-r7x1oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:toggle-switch-on" {...props}></Icon>
