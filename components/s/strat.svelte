<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m79_piezz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m79_piezz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:strat" {...props}></Icon>
