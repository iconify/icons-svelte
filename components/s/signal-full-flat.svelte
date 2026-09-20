<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iggb9bb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iggb9bb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:signal-full-flat" {...props}></Icon>
