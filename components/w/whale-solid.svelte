<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l21nl5osl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l21nl5osl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:whale-solid" {...props}></Icon>
