<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ymvhzeq.css';
import '../../css/f/fxgii4b0e.css';
import '../../css/g/gh0u09crw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b7ymvhzeq"/><path class="fxgii4b0e"/><path class="gh0u09crw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:second-life-battery-48-bold" {...props}></Icon>
