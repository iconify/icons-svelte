<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhxljyxlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhxljyxlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:run-fill" {...props}></Icon>
