<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to3-oybdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to3-oybdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shadows-filled" {...props}></Icon>
