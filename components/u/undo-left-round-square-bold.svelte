<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx9oaobmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lx9oaobmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-round-square-bold" {...props}></Icon>
