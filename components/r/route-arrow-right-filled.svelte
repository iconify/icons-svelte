<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8z6jub6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8z6jub6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:route-arrow-right-filled" {...props}></Icon>
