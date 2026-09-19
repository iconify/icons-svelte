<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx2i-ob8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx2i-ob8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:spoon" {...props}></Icon>
