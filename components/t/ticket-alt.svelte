<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq6h8d1ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq6h8d1ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ticket-alt" {...props}></Icon>
