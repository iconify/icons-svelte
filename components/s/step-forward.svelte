<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpjm6jbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="xpjm6jbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:step-forward" {...props}></Icon>
