<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osmsw0baw.css';
import '../../css/u/u7-rv5cxi.css';
import '../../css/u/ujxr68ihv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="osmsw0baw"/><path class="u7-rv5cxi"/><path class="ujxr68ihv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:sim-card" {...props}></Icon>
