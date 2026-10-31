<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_olhgb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_olhgb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-check-fill-round" {...props}></Icon>
