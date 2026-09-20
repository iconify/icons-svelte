<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1ibt0bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1ibt0bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:transmission" {...props}></Icon>
