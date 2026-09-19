<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ai75bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="q3ai75bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:twitter" {...props}></Icon>
