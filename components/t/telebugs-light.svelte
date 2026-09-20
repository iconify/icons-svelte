<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb7coib4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb7coib4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:telebugs-light" {...props}></Icon>
