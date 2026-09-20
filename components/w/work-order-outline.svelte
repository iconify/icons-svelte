<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgq75lbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lgq75lbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-outline" {...props}></Icon>
