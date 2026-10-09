<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly6i-fbqm.css';
import '../../css/n/ndjzvdb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ly6i-fbqm"/><path class="ndjzvdb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snowboard-48" {...props}></Icon>
