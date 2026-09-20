<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7coa3b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7coa3b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ryanair" {...props}></Icon>
