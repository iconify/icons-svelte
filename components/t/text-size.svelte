<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2bjhb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="co2bjhb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:text-size" {...props}></Icon>
