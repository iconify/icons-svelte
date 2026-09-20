<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx9a00_2h.css';
import '../../css/d/drkyq1beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx9a00_2h"/><path class="drkyq1beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:zip-file-compress-bold" {...props}></Icon>
