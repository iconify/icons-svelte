<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpac6cbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jpac6cbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-energy-converter-20" {...props}></Icon>
