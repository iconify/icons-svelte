<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9sagjzat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l9sagjzat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-on-water" {...props}></Icon>
