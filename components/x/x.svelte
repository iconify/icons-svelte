<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0mqnen7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0mqnen7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:x" {...props}></Icon>
