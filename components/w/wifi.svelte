<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/punal9bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":661};
const content = `<path class="punal9bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:wifi" {...props}></Icon>
