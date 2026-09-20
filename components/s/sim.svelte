<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5v32bcqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r5v32bcqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sim" {...props}></Icon>
