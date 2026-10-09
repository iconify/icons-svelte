<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q85exbg4c.css';
import '../../css/s/sy0-p47dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q85exbg4c"/><path class="sy0-p47dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screwdriver-20" {...props}></Icon>
