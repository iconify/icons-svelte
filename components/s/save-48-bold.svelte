<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngycp3qcw.css';
import '../../css/o/obdvgrbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ngycp3qcw"/><path class="obdvgrbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:save-48-bold" {...props}></Icon>
