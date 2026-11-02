<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mew4heblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mew4heblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-fill" {...props}></Icon>
