<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn-a9rbco.css';
import '../../css/g/g0ni6vb5b.css';
import '../../css/t/t0ojj79_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zn-a9rbco"/><path class="g0ni6vb5b"/><path class="t0ojj79_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scour-protection-20" {...props}></Icon>
