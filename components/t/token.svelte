<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp40olbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hp40olbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:token" {...props}></Icon>
