<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx93idbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx93idbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-terminal-round" {...props}></Icon>
