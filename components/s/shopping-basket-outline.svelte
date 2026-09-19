<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfdvjkbvs.css';
import '../../css/c/c6rg3sbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfdvjkbvs"/><path clip-rule="evenodd" class="c6rg3sbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shopping-basket-outline" {...props}></Icon>
