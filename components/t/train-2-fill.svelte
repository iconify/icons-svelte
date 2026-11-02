<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj70rrbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj70rrbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-2-fill" {...props}></Icon>
