<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj_1-1b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oj_1-1b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-dim-48-bold" {...props}></Icon>
