<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lae5htber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lae5htber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:warehouse-pre-filled" {...props}></Icon>
