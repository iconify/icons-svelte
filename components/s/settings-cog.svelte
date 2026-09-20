<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a78dyvbwf.css';
import '../../css/o/ooikihlll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a78dyvbwf"/><path class="ooikihlll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:settings-cog" {...props}></Icon>
