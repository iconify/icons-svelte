<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw53-sbdu.css';
import '../../css/b/b_6nlsbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw53-sbdu"/><path class="b_6nlsbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-meter-48" {...props}></Icon>
