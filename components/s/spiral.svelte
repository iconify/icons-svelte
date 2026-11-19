<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vde0oz-fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vde0oz-fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:spiral" {...props}></Icon>
