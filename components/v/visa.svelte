<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg45qdbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kg45qdbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:visa" {...props}></Icon>
