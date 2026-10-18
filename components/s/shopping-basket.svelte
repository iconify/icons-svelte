<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_1julbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_1julbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shopping-basket" {...props}></Icon>
