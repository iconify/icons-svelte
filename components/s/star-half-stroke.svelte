<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe4_vg-gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xe4_vg-gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:star-half-stroke" {...props}></Icon>
