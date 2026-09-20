<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exvhs1b_r.css';
import '../../css/k/klb_tkdzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exvhs1b_r"/><path clip-rule="evenodd" class="klb_tkdzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:router-modem-fill" {...props}></Icon>
