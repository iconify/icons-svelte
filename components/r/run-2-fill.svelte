<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5uzgkztg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5uzgkztg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:run-2-fill" {...props}></Icon>
