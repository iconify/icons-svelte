<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibmfn8bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ibmfn8bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:spade-suit" {...props}></Icon>
