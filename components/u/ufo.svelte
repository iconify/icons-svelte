<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8hp_8b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w8hp_8b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ufo" {...props}></Icon>
