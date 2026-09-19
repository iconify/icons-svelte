<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npn5p1brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":963,"height":1000};
const content = `<path class="npn5p1brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:signal" {...props}></Icon>
