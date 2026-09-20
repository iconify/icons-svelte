<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih9_-c6ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":192};
const content = `<path class="ih9_-c6ca x19hqcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:threads-dark" {...props}></Icon>
