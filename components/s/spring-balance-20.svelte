<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcnvp-btz.css';
import '../../css/y/ygre9pbqx.css';
import '../../css/t/t75ay3btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lcnvp-btz"/><path class="ygre9pbqx"/><path class="t75ay3btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spring-balance-20" {...props}></Icon>
