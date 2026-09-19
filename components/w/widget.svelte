<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzeym_bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rzeym_bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:widget" {...props}></Icon>
