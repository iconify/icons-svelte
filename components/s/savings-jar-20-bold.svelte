<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtdrk6b1n.css';
import '../../css/m/moe3g5b7s.css';
import '../../css/h/hvh37gb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mtdrk6b1n"/><path class="moe3g5b7s"/><path class="hvh37gb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:savings-jar-20-bold" {...props}></Icon>
