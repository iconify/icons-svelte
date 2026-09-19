<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iajkaacuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":735};
const content = `<path class="iajkaacuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:t-upper-case" {...props}></Icon>
