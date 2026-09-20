<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e58pc83mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e58pc83mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sparkles-fill-24" {...props}></Icon>
