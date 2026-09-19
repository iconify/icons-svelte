<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1q_xb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py1q_xb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:twitch-outline" {...props}></Icon>
