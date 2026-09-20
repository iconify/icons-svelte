<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzeka9dub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzeka9dub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:search" {...props}></Icon>
