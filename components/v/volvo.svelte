<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juxie3vlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juxie3vlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:volvo" {...props}></Icon>
