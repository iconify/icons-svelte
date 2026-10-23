<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4klm8bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4klm8bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:spell-check-2" {...props}></Icon>
