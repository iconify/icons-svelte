<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe1v0h6hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fe1v0h6hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort-amount-down-alt" {...props}></Icon>
