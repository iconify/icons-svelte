<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g45lxybwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g45lxybwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:submit-outline" {...props}></Icon>
