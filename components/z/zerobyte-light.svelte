<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6r87g8pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6r87g8pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zerobyte-light" {...props}></Icon>
