<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3bhoub7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3bhoub7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trees-solid" {...props}></Icon>
