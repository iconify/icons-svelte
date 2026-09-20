<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe1f4abji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qe1f4abji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skateboard-deck" {...props}></Icon>
