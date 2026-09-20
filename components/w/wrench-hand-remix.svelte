<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esfupwbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="esfupwbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:wrench-hand-remix" {...props}></Icon>
