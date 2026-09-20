<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk-_a8_0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fk-_a8_0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tent" {...props}></Icon>
