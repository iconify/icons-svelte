<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys6lkqbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ys6lkqbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:rust-alt" {...props}></Icon>
