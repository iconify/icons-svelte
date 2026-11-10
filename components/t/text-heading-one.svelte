<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtf68bbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtf68bbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-heading-one" {...props}></Icon>
