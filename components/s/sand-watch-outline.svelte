<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9s8gdcsr.css';
import '../../css/g/gs-juzbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9s8gdcsr"/><path clip-rule="evenodd" class="gs-juzbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:sand-watch-outline" {...props}></Icon>
