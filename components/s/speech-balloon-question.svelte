<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mirhpy0av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mirhpy0av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-question" {...props}></Icon>
