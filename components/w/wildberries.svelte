<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o51vhd6du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":75.1};
const content = `<path class="o51vhd6du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wildberries" {...props}></Icon>
