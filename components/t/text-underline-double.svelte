<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz_1w_b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz_1w_b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-underline-double" {...props}></Icon>
