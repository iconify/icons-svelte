<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d30kfbc6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d30kfbc6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:send" {...props}></Icon>
