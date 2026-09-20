<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c54w_tbjw.css';
import '../../css/i/ifd5f2bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c54w_tbjw"/><path class="ifd5f2bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wave-hand-fill" {...props}></Icon>
