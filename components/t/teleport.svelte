<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz_npsbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mz_npsbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:teleport" {...props}></Icon>
