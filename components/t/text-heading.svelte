<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvwsaw3cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvwsaw3cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-heading" {...props}></Icon>
