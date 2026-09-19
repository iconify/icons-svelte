<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6vi1xb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="n6vi1xb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:star" {...props}></Icon>
