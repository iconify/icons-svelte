<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6lm62c3l.css';
import '../../css/h/hkazuhb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6lm62c3l"/><circle class="hkazuhb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thermometer-outline" {...props}></Icon>
