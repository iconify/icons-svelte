<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgre77bfz.css';
import '../../css/p/pk8m0abcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cgre77bfz"/><path class="pk8m0abcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wire-stripper-48" {...props}></Icon>
