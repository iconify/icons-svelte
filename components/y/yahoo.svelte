<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyus6l67b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wyus6l67b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:yahoo" {...props}></Icon>
