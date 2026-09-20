<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9g2sprop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="o9g2sprop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:wall-front" {...props}></Icon>
