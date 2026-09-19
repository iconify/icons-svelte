<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb0rhnbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xb0rhnbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zendesk" {...props}></Icon>
