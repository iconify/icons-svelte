<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdzm7zkpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wdzm7zkpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni5f3a-box" {...props}></Icon>
