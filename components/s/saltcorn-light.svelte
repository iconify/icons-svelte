<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8l9hqbrf.css';
import '../../css/n/nz0jllbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k8l9hqbrf"/><path class="nz0jllbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:saltcorn-light" {...props}></Icon>
