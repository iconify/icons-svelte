<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue64i0bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue64i0bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-03" {...props}></Icon>
