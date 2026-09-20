<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onkjj_flp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="onkjj_flp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-amount-down-solid" {...props}></Icon>
