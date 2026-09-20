<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smp8q2bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smp8q2bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch-later" {...props}></Icon>
