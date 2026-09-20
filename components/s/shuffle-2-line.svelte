<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4i8x7b6y.css';
import '../../css/s/scxgi4bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4i8x7b6y"/><path class="scxgi4bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shuffle-2-line" {...props}></Icon>
