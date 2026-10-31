<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx64cwy3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx64cwy3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spell-check-fill-round" {...props}></Icon>
