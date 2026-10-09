<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utcxkkbxw.css';
import '../../css/g/gtg_bmb_n.css';
import '../../css/t/t87_xhoos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="utcxkkbxw"/><path class="gtg_bmb_n"/><path class="t87_xhoos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tree-20-bold" {...props}></Icon>
