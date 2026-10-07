<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ggb4u2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ggb4u2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-dashed" {...props}></Icon>
