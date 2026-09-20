<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j20z8obis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j20z8obis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unmute" {...props}></Icon>
