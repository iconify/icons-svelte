<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of1ohj7_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="of1ohj7_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vpn-connection" {...props}></Icon>
