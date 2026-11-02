<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfi-3h6ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfi-3h6ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-2-line" {...props}></Icon>
