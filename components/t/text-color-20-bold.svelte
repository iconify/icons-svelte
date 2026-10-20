<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z53lt7bqm.css';
import '../../css/u/ul7690b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z53lt7bqm"/><path class="ul7690b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-color-20-bold" {...props}></Icon>
