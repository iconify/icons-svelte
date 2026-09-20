<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-bxn1n6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m-bxn1n6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:target" {...props}></Icon>
