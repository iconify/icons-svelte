<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt560hjnz.css';
import '../../css/b/bk7elybvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt560hjnz"/><path class="bk7elybvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:waze" {...props}></Icon>
