<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq8cixbfp.css';
import '../../css/f/fp3l73glm.css';
import '../../css/h/hqg92z8bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq8cixbfp"/><path clip-rule="evenodd" class="fp3l73glm"/><path class="hqg92z8bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:university-filled" {...props}></Icon>
