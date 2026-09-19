<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdi1d-bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdi1d-bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sd-card" {...props}></Icon>
