<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sam6x3bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sam6x3bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:sort-az" {...props}></Icon>
