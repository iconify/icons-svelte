<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvz8bznxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hvz8bznxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:step-2" {...props}></Icon>
