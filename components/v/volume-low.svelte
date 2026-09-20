<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojw0e_9cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ojw0e_9cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:volume-low" {...props}></Icon>
