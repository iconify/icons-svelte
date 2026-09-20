<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j48h6jphd.css';
import '../../css/l/l9a7ocbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="j48h6jphd"/><path class="l9a7ocbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisparr" {...props}></Icon>
