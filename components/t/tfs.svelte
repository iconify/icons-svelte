<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao1ao21el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":510,"height":512};
const content = `<path class="ao1ao21el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tfs" {...props}></Icon>
