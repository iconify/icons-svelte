<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dddisgzym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b dddisgzym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:uber" {...props}></Icon>
