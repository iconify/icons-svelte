<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7u8429br.css';
import '../../css/q/qwf60s-8o.css';
import '../../css/p/phlrdv_7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7u8429br"/><path clip-rule="evenodd" class="qwf60s-8o"/><path class="phlrdv_7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stripe" {...props}></Icon>
