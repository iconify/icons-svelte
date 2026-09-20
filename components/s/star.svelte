<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5zs_rrj.css';
import '../../css/d/da75vnbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="vc5zs_rrj"/><path class="da75vnbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:star" {...props}></Icon>
