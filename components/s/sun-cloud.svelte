<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg7x63d-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rg7x63d-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sun-cloud" {...props}></Icon>
