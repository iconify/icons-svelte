<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnk6u5eey.css';
import '../../css/s/sd_7wj8_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nnk6u5eey"/><path class="sd_7wj8_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:twig" {...props}></Icon>
