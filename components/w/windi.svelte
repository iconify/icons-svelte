<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye5sjf4mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ye5sjf4mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:windi" {...props}></Icon>
