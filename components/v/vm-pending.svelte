<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcf0dwdjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zcf0dwdjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vm-pending" {...props}></Icon>
