<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pttzn-btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pttzn-btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:tally-two" {...props}></Icon>
