<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs09_bb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gs09_bb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rugby" {...props}></Icon>
