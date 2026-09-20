<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb3m0hb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tb3m0hb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-end-help" {...props}></Icon>
