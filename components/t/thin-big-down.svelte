<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0aox4ish.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0aox4ish"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:thin-big-down" {...props}></Icon>
