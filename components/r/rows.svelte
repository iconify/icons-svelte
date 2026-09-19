<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbtm1819t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbtm1819t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rows" {...props}></Icon>
