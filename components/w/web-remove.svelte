<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl3_lhdlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl3_lhdlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-remove" {...props}></Icon>
