<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2072ym-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="y2072ym-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:wordpress-wordmark" {...props}></Icon>
