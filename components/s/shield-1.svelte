<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv-_es__f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qv-_es__f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-1" {...props}></Icon>
