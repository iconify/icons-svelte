<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bev78jbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bev78jbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-filled" {...props}></Icon>
