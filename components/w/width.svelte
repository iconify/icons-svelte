<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlsucpw_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dlsucpw_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:width" {...props}></Icon>
