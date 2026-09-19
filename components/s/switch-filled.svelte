<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oscgc-brr.css';
import '../../css/r/rukfmib6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oscgc-brr"/><path class="rukfmib6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:switch-filled" {...props}></Icon>
