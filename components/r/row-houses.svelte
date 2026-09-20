<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzky8c53b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jzky8c53b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:row-houses" {...props}></Icon>
