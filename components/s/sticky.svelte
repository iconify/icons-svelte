<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es1mdt2en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="es1mdt2en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sticky" {...props}></Icon>
