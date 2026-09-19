<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_1_ebbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2080,"height":1504};
const content = `<path class="n_1_ebbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:timeslots" {...props}></Icon>
