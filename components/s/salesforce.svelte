<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9xd_5ayx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o9xd_5ayx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:salesforce" {...props}></Icon>
