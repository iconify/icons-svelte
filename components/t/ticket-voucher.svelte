<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct4igk9uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct4igk9uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:ticket-voucher" {...props}></Icon>
