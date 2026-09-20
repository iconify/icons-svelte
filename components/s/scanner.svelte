<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmna-ibde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wmna-ibde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:scanner" {...props}></Icon>
