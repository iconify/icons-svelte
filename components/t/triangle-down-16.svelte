<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spo-uibbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spo-uibbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-down-16" {...props}></Icon>
