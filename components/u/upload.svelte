<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knrki_leo.css';
import '../../css/z/z9sersb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="knrki_leo"/><path class="z9sersb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:upload" {...props}></Icon>
