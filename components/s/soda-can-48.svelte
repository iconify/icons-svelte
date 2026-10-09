<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8div7b-m.css';
import '../../css/p/placboblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z8div7b-m"/><path class="placboblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soda-can-48" {...props}></Icon>
