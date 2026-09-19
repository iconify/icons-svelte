<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcln_tb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lcln_tb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:umbrella" {...props}></Icon>
