<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qahyg6byo.css';
import '../../css/z/zu_sz4rou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qahyg6byo"/><path clip-rule="evenodd" class="zu_sz4rou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-stop-filled" {...props}></Icon>
