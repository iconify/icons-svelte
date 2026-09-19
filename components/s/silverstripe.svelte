<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3t2e4m8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1022};
const content = `<path class="t3t2e4m8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:silverstripe" {...props}></Icon>
