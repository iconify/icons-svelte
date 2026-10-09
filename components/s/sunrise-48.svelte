<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-taz-bdu.css';
import '../../css/f/ftnl01noy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p-taz-bdu"/><path class="ftnl01noy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunrise-48" {...props}></Icon>
