<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sga9agb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sga9agb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:stackoverflow-square" {...props}></Icon>
