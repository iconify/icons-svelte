<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo_iicc4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qo_iicc4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:visa" {...props}></Icon>
