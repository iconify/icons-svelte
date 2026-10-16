<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-lmpi58f.css';
import '../../css/y/y3ceaebkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q-lmpi58f"/><path class="y3ceaebkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ups-48-bold" {...props}></Icon>
