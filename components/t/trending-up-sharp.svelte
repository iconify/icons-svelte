<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0daysu1p.css';
import '../../css/q/qnkrgpaud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0daysu1p"/><path class="qnkrgpaud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trending-up-sharp" {...props}></Icon>
