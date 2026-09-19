<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/titw2rw2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="titw2rw2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:scirate-square" {...props}></Icon>
