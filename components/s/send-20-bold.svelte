<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z63nbsbdb.css';
import '../../css/h/hjq60mx9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z63nbsbdb"/><path class="hjq60mx9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-20-bold" {...props}></Icon>
