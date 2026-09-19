<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qesz6wb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qesz6wb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:yammer" {...props}></Icon>
