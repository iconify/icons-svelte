<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmgk-1e4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nmgk-1e4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-numeric" {...props}></Icon>
