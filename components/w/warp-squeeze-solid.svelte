<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl2fbrcrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jl2fbrcrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:warp-squeeze-solid" {...props}></Icon>
