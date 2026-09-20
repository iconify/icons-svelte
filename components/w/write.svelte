<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx-k1mb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nx-k1mb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:write" {...props}></Icon>
