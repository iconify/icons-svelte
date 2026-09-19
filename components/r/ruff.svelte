<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ja0lbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h_ja0lbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:ruff" {...props}></Icon>
