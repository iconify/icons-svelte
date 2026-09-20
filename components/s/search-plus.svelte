<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw0_7ow_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw0_7ow_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:search-plus" {...props}></Icon>
