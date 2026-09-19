<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc_2esbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc_2esbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:t-shirt-outline" {...props}></Icon>
