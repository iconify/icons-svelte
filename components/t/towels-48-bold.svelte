<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2i7lbka.css';
import '../../css/p/p64m754zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="db2i7lbka"/><path class="p64m754zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:towels-48-bold" {...props}></Icon>
