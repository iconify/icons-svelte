<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-9h9wb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-9h9wb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:snowman-solid" {...props}></Icon>
