<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8p397xka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k8p397xka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-circle-rectangle" {...props}></Icon>
