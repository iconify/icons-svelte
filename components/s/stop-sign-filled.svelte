<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1tsy5brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s1tsy5brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stop-sign-filled" {...props}></Icon>
