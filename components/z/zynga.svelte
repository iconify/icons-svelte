<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dobfjlbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":488};
const content = `<path class="dobfjlbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:zynga" {...props}></Icon>
