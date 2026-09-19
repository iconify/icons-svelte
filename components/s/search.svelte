<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crvea6bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="crvea6bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:search" {...props}></Icon>
