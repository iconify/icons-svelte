<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7pgm6_vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="b7pgm6_vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-end-alert" {...props}></Icon>
