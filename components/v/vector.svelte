<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l76j_08rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l76j_08rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vector" {...props}></Icon>
