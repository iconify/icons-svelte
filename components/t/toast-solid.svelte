<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4m87fb-g.css';
import '../../css/v/vmlbxu0qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j4m87fb-g"/><path clip-rule="evenodd" class="vmlbxu0qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:toast-solid" {...props}></Icon>
