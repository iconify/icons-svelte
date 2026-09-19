<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uosdpd3li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uosdpd3li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unlocked" {...props}></Icon>
