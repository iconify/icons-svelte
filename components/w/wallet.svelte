<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vefoirb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vefoirb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:wallet" {...props}></Icon>
