<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiwkhfbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="wiwkhfbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:textfield" {...props}></Icon>
