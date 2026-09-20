<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcj7e-b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":73};
const content = `<path class="kcj7e-b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:valkey" {...props}></Icon>
