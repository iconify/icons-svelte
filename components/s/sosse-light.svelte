<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fidkc1bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fidkc1bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sosse-light" {...props}></Icon>
