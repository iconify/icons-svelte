<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiosb2sjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hiosb2sjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shirt-48-bold" {...props}></Icon>
