<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8wtxcbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8wtxcbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:wine-remix" {...props}></Icon>
