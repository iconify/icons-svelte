<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6deh2baw.css';
import '../../css/c/cq41npglk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q6deh2baw"/><path class="cq41npglk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:unlock-48" {...props}></Icon>
