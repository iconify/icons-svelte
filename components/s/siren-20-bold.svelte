<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-0g-v3zq.css';
import '../../css/l/lnh0e5bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z-0g-v3zq"/><path class="lnh0e5bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:siren-20-bold" {...props}></Icon>
