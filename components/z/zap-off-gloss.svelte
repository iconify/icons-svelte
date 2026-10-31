<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4w5a7bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4w5a7bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-off-gloss" {...props}></Icon>
