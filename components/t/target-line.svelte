<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxy6v3jpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxy6v3jpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:target-line" {...props}></Icon>
