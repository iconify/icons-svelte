<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3o7nr65w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3o7nr65w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sandbox" {...props}></Icon>
