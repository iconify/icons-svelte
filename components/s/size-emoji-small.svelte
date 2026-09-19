<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw-zpcb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lw-zpcb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:size-emoji-small" {...props}></Icon>
