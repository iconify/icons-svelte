<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyf10rbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="vyf10rbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:three-bars" {...props}></Icon>
