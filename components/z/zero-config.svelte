<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys8spe0-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys8spe0-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zero-config" {...props}></Icon>
