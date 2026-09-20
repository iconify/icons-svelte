<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3fhp9b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3fhp9b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vector-light" {...props}></Icon>
