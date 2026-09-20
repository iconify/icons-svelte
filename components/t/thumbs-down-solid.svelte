<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crbcj0blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="crbcj0blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thumbs-down-solid" {...props}></Icon>
