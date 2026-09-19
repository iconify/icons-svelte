<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytzcdhe_p.css';
import '../../css/r/rsl89ccpi.css';
import '../../css/g/gxtb8y-ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ytzcdhe_p"/><path class="rsl89ccpi"/><path class="gxtb8y-ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:serverless-fleet" {...props}></Icon>
