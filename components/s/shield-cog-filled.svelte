<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt1f5_b9q.css';
import '../../css/n/nvh489vpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt1f5_b9q"/><path clip-rule="evenodd" class="nvh489vpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-cog-filled" {...props}></Icon>
