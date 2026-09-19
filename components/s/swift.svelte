<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af_xcxbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="af_xcxbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:swift" {...props}></Icon>
