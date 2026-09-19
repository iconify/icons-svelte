<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmhl_gbis.css';
import '../../css/s/ssrw9lb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmhl_gbis"/><path clip-rule="evenodd" class="ssrw9lb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:trash-alt-outline" {...props}></Icon>
