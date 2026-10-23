<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qse2q7bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qse2q7bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tombstone-filled" {...props}></Icon>
