<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0-webzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ak0-webzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tab" {...props}></Icon>
