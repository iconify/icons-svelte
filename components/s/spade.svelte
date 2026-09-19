<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohmp0hbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmp0hbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:spade" {...props}></Icon>
