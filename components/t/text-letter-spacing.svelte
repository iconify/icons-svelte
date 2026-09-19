<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6qsnzvxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6qsnzvxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-letter-spacing" {...props}></Icon>
