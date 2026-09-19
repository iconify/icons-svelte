<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dybwt5b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dybwt5b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ticket-perferated-fill" {...props}></Icon>
