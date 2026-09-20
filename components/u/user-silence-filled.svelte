<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1xwpsfel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r1xwpsfel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-silence-filled" {...props}></Icon>
