<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-du2nvlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-du2nvlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:ruby" {...props}></Icon>
