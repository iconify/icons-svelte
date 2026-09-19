<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-wij4i-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-wij4i-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:subway-sharp" {...props}></Icon>
