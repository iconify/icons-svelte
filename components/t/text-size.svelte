<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqtxuqbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="rqtxuqbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:text-size" {...props}></Icon>
