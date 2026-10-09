<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg054wh3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xg054wh3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-48" {...props}></Icon>
