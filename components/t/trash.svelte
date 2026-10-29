<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxkycjbej.css';
import '../../css/f/fff81-bmi.css';
import '../../css/f/flstcrbhi.css';
import '../../css/o/o71e8i_kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxkycjbej wm-a"/><path class="fff81-bmi wm-k"/><path class="flstcrbhi wm-k"/><path class="o71e8i_kg wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:trash" {...props}></Icon>
