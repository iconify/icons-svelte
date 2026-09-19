<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq7m4_bez.css';
import '../../css/m/mxlpzmyqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq7m4_bez"/><path class="mxlpzmyqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:virtual-reality-outlined" {...props}></Icon>
