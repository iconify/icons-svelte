<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm5up5pot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm5up5pot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sleigh-fill" {...props}></Icon>
