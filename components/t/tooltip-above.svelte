<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibh-pxvmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ibh-pxvmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-above" {...props}></Icon>
