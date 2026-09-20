<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k64a_t5ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k64a_t5ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:wind" {...props}></Icon>
