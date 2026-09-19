<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfcwc_bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfcwc_bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-lock-filled" {...props}></Icon>
