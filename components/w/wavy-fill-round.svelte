<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9b5wab0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9b5wab0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-fill-round" {...props}></Icon>
