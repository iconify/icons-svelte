<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc-_0tbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cc-_0tbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sword-fill" {...props}></Icon>
