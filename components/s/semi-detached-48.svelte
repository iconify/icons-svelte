<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu2vshdfm.css';
import '../../css/c/ctjzoy1eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qu2vshdfm"/><path class="ctjzoy1eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semi-detached-48" {...props}></Icon>
