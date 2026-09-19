<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t77fmmb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t77fmmb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ticket-fill" {...props}></Icon>
