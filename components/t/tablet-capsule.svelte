<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp1806bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gp1806bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tablet-capsule" {...props}></Icon>
