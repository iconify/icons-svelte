<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b44m8kb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b44m8kb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:text-style-flat" {...props}></Icon>
