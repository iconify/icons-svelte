<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzvq67bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzvq67bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tree-3" {...props}></Icon>
