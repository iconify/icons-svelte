<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spd74y6rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spd74y6rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:zig" {...props}></Icon>
