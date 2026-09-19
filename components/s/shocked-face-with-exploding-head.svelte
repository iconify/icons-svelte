<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaus4hbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eaus4hbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:shocked-face-with-exploding-head" {...props}></Icon>
