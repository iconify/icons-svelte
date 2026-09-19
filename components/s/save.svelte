<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly7t4lb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":496};
const content = `<path class="ly7t4lb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:save" {...props}></Icon>
