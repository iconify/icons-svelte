<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdabxtboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdabxtboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:youtube-alt" {...props}></Icon>
