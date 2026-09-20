<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plyct1bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plyct1bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:space" {...props}></Icon>
