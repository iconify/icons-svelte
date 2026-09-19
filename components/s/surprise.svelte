<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt6-q7b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="dt6-q7b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:surprise" {...props}></Icon>
