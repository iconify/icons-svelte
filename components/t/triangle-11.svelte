<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve_zacdrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ve_zacdrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:triangle-11" {...props}></Icon>
