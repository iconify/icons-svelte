<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcfgh-bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcfgh-bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:splunk-dark" {...props}></Icon>
