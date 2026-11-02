<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te7x2geix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te7x2geix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-4-line" {...props}></Icon>
