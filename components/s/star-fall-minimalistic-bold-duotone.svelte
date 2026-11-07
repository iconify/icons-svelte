<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wahoyrbda.css';
import '../../css/p/p0h48vbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wahoyrbda"/><path clip-rule="evenodd" class="p0h48vbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-minimalistic-bold-duotone" {...props}></Icon>
