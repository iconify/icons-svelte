<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbo5-pbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="jbo5-pbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:shield-security" {...props}></Icon>
