<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex_0f5bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex_0f5bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:telescope-2-fill" {...props}></Icon>
