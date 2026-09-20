<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3np6cb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3np6cb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:slint" {...props}></Icon>
