<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de09431ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de09431ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tree-round-dot-vertical-filled" {...props}></Icon>
