<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra8bklu7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ra8bklu7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:sticky-note" {...props}></Icon>
