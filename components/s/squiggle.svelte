<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz26tircu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz26tircu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:squiggle" {...props}></Icon>
