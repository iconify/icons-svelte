<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cswx4ybwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cswx4ybwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:wall-front-damaged" {...props}></Icon>
