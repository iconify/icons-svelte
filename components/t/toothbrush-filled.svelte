<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7yw6gb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7yw6gb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:toothbrush-filled" {...props}></Icon>
