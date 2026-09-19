<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg8w73bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg8w73bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sliding-window-door-open" {...props}></Icon>
