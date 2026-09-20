<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn06cubph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn06cubph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:stars-a" {...props}></Icon>
