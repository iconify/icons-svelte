<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8rpnac1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q8rpnac1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:shopping-bag" {...props}></Icon>
