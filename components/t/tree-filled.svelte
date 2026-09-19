<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1-c0l79h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1-c0l79h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tree-filled" {...props}></Icon>
