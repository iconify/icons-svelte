<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2jjx11ma.css';
import '../../css/v/vikp09bur.css';
import '../../css/o/o2pbh_bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p2jjx11ma"/><path class="vikp09bur"/><path class="o2pbh_bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whale-48" {...props}></Icon>
