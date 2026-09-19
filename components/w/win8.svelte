<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii_1hrz-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":986,"height":1000};
const content = `<path class="ii_1hrz-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:win8" {...props}></Icon>
