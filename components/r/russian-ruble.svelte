<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stw9hsbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stw9hsbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:russian-ruble" {...props}></Icon>
