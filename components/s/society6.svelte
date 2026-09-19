<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mycjnlsig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mycjnlsig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:society6" {...props}></Icon>
