<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slplf4wxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="slplf4wxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:translation" {...props}></Icon>
