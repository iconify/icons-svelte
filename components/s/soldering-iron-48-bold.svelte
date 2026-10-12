<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aft-_hbdu.css';
import '../../css/i/i-s48fubu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aft-_hbdu"/><path class="i-s48fubu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soldering-iron-48-bold" {...props}></Icon>
