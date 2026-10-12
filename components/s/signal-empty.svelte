<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fip2h6bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fip2h6bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:signal-empty" {...props}></Icon>
