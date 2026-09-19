<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6ndv5-vm.css';
import '../../css/f/fiwf45bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<rect class="p6ndv5-vm"/><path class="fiwf45bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:table-fill-12" {...props}></Icon>
