<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd9ctrbds.css';
import '../../css/h/h-zg-r21y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dd9ctrbds"/><path class="h-zg-r21y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:subscript-48-bold" {...props}></Icon>
