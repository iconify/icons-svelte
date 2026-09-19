<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwm4we_ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="uwm4we_ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:shield" {...props}></Icon>
