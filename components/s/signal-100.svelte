<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s26tlbbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s26tlbbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-100" {...props}></Icon>
