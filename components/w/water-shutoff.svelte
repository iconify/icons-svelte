<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y40u92bbl.css';
import '../../css/e/ejog3cncc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y40u92bbl"/><path class="ejog3cncc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:water-shutoff" {...props}></Icon>
