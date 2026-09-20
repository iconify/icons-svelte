<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8nppju6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8nppju6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sun-moon" {...props}></Icon>
