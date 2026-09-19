<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3gt3fbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3gt3fbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:terminal-square-filled" {...props}></Icon>
