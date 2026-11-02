<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io3z3bc1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io3z3bc1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-half-line" {...props}></Icon>
