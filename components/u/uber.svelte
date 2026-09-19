<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9er9icpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k9er9icpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:uber" {...props}></Icon>
