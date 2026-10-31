<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwl12gbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwl12gbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-up-fill-round" {...props}></Icon>
