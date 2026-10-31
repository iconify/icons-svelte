<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3__ojbef.css';
import '../../css/u/u9lqayb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3__ojbef"/><path clip-rule="evenodd" class="u9lqayb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-q-filled" {...props}></Icon>
