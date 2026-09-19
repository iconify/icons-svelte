<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7fm_bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx7fm_bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:windows-old" {...props}></Icon>
