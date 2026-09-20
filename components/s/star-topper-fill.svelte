<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2yg04bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2yg04bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-topper-fill" {...props}></Icon>
