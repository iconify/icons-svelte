<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzflhmqcl.css';
import '../../css/h/hvkkpmbju.css';
import '../../css/h/h8goprb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dzflhmqcl"/><path class="hvkkpmbju"/><path class="h8goprb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:xor-gate-20-bold" {...props}></Icon>
