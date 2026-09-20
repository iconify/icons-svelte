<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td5yvf_el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td5yvf_el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:steemit" {...props}></Icon>
