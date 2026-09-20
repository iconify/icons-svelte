<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euz3adbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="euz3adbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:take-off-remix" {...props}></Icon>
