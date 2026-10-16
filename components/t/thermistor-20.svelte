<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr-mm0bik.css';
import '../../css/f/f_pk9vbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kr-mm0bik"/><path class="f_pk9vbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermistor-20" {...props}></Icon>
