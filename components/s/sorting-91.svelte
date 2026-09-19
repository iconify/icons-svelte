<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-rseb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-rseb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-91" {...props}></Icon>
