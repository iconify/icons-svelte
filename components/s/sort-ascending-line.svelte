<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ameepbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-ameepbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sort-ascending-line" {...props}></Icon>
