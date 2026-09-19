<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x12q_okfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x12q_okfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:stak" {...props}></Icon>
