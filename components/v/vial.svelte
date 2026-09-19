<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ntt-odb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ntt-odb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:vial" {...props}></Icon>
