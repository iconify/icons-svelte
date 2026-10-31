<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7_41xs_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7_41xs_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-left-fill-round" {...props}></Icon>
