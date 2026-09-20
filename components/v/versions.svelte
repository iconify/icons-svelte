<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it4ovqb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="it4ovqb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:versions" {...props}></Icon>
