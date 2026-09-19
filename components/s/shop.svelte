<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed-s9pbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1472};
const content = `<path class="ed-s9pbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:shop" {...props}></Icon>
