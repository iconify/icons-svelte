<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4s4u8b9z.css';
import '../../css/o/ortpaq31n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4s4u8b9z"/><path class="ortpaq31n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-bold-duotone" {...props}></Icon>
