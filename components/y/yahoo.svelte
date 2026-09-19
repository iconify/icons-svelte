<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re-sap6xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="re-sap6xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:yahoo" {...props}></Icon>
