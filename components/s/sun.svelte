<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h69r-hbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h69r-hbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sun" {...props}></Icon>
