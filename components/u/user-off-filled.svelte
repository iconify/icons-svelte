<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lii6gfblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lii6gfblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-off-filled" {...props}></Icon>
