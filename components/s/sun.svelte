<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o100tzgov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o100tzgov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:sun" {...props}></Icon>
