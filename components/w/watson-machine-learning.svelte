<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2_a8x_yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b2_a8x_yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:watson-machine-learning" {...props}></Icon>
