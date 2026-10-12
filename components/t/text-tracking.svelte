<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vomyfrboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vomyfrboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-tracking" {...props}></Icon>
