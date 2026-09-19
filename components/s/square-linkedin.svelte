<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shqpe6bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="shqpe6bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-linkedin" {...props}></Icon>
