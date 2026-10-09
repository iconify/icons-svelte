<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b97769rea.css';
import '../../css/n/nssl3jbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b97769rea"/><path class="nssl3jbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-asc-48-bold" {...props}></Icon>
