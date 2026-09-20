<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr_i2abbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nr_i2abbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:smoke-curl" {...props}></Icon>
