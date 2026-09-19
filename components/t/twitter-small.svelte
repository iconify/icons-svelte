<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e00l-by_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e00l-by_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:twitter-small" {...props}></Icon>
