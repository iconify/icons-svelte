<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itdhzz-ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itdhzz-ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transform-filled" {...props}></Icon>
