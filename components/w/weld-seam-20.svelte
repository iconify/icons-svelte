<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea2kc5baq.css';
import '../../css/o/obkbes3ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ea2kc5baq"/><path class="obkbes3ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weld-seam-20" {...props}></Icon>
