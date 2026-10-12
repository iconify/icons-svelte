<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr-zs8cga.css';
import '../../css/o/ooobm-34o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tr-zs8cga"/><path class="ooobm-34o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:turtle-20-bold" {...props}></Icon>
