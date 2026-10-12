<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltmjp_5as.css';
import '../../css/g/gs4dp93ml.css';
import '../../css/f/f_ydpsblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltmjp_5as"/><path class="gs4dp93ml"/><path class="f_ydpsblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-all-filled" {...props}></Icon>
