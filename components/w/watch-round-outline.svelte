<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh8x5liyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qh8x5liyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-round-outline" {...props}></Icon>
