<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddyiizyok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ddyiizyok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:user-group" {...props}></Icon>
