<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bujsw6-zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bujsw6-zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:virtual-reality-remix" {...props}></Icon>
