<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u99antbvu.css';
import '../../css/s/sby6-kb3l.css';
import '../../css/z/z9sww47-j.css';
import '../../css/z/zreo3t4eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u99antbvu"/><path class="sby6-kb3l"/><path clip-rule="evenodd" class="z9sww47-j"/><path clip-rule="evenodd" class="zreo3t4eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-2-outline" {...props}></Icon>
