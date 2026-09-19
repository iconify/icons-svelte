<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbimk5bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hbimk5bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-circle-block" {...props}></Icon>
