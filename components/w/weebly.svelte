<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj8grqbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tj8grqbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:weebly" {...props}></Icon>
