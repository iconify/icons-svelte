<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bprw-4yaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bprw-4yaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shuffle-gloss" {...props}></Icon>
