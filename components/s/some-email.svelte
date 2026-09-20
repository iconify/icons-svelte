<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbn_t3z4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbn_t3z4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-email" {...props}></Icon>
