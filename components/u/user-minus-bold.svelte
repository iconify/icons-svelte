<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg261rb8a.css';
import '../../css/w/w8x_vkwlh.css';
import '../../css/l/lc21qzuqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg261rb8a"/><path clip-rule="evenodd" class="w8x_vkwlh"/><path class="lc21qzuqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-minus-bold" {...props}></Icon>
