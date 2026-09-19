<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mstk5vbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mstk5vbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:vrsc" {...props}></Icon>
