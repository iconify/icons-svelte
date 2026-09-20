<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l886_s5ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="l886_s5ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:text-image" {...props}></Icon>
