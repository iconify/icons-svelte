<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imdqhbpbn.css';
import '../../css/i/i3t22pyfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imdqhbpbn"/><path class="i3t22pyfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:winrar-bold" {...props}></Icon>
