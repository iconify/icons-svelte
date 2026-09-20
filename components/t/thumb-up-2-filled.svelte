<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiajuac3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiajuac3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:thumb-up-2-filled" {...props}></Icon>
