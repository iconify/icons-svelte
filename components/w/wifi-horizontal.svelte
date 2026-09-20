<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1hf5acsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="v1hf5acsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:wifi-horizontal" {...props}></Icon>
