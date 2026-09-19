<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg99yvkdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eg99yvkdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:table-link" {...props}></Icon>
