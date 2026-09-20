<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmf1tu78z.css';
import '../../css/p/pc6urubdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmf1tu78z"/><path class="pc6urubdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-5-line" {...props}></Icon>
