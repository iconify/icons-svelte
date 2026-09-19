<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj7n45bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="aj7n45bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:skull-crossbones" {...props}></Icon>
