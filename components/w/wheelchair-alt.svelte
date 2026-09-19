<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m18m25u6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="m18m25u6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wheelchair-alt" {...props}></Icon>
