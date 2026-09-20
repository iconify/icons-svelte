<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t13a7cmwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t13a7cmwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tire" {...props}></Icon>
