<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s02m9kbje.css';
import '../../css/p/pcxgyzb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s02m9kbje"/><path class="pcxgyzb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wealth-filled" {...props}></Icon>
