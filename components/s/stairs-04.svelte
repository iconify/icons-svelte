<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knk5ty9ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knk5ty9ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stairs-04" {...props}></Icon>
