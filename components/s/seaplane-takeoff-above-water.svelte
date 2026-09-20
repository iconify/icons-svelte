<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjfe1bcyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kjfe1bcyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-takeoff-above-water" {...props}></Icon>
