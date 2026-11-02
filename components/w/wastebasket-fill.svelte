<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz4u7tcag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz4u7tcag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wastebasket-fill" {...props}></Icon>
