<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxj7stbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxj7stbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal" {...props}></Icon>
