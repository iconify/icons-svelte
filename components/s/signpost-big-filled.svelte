<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo1yws-pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo1yws-pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:signpost-big-filled" {...props}></Icon>
