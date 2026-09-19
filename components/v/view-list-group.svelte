<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdk52cczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qdk52cczp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:view-list-group" {...props}></Icon>
