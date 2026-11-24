<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yojs9sdcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yojs9sdcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scroll-filled" {...props}></Icon>
