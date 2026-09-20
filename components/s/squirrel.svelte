<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b34v4yqmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b34v4yqmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:squirrel" {...props}></Icon>
