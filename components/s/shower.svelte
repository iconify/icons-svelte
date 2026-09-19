<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt1ux1bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt1ux1bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shower" {...props}></Icon>
