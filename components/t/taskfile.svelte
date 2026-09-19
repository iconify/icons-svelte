<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eewmafs7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eewmafs7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:taskfile" {...props}></Icon>
