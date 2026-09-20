<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6quz83kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n6quz83kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-none-solid" {...props}></Icon>
