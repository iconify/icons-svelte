<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9pdrvokh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9pdrvokh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:skull-1-bold" {...props}></Icon>
