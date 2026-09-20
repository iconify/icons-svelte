<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soceu0b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="soceu0b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sauvastika-with-dots" {...props}></Icon>
