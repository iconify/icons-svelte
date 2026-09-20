<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjxa01b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yjxa01b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:toaster-remix" {...props}></Icon>
