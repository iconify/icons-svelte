<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td162ub0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="td162ub0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:users" {...props}></Icon>
