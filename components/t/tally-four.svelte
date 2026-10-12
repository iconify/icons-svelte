<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op4b25bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op4b25bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:tally-four" {...props}></Icon>
