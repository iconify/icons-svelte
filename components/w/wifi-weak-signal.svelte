<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olzhhdczn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="olzhhdczn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wifi-weak-signal" {...props}></Icon>
