<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp8ccub7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gp8ccub7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:screw" {...props}></Icon>
