<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p40iouuix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p40iouuix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-bold" {...props}></Icon>
