<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9xr5p5ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9xr5p5ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:ruler" {...props}></Icon>
