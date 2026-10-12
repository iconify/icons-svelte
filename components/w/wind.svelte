<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu3cezbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu3cezbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:wind" {...props}></Icon>
