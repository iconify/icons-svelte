<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vufao1btt.css';
import '../../css/q/q59a9ubij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vufao1btt"/><path class="q59a9ubij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-thermal-20" {...props}></Icon>
