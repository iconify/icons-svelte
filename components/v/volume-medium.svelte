<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8i-_-z1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h8i-_-z1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:volume-medium" {...props}></Icon>
