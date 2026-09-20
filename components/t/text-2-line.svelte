<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du1gcbhpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du1gcbhpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-2-line" {...props}></Icon>
