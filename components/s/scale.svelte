<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtgmf5b6d.css';
import '../../css/x/x4ya1hbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qtgmf5b6d"/><path class="x4ya1hbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scale" {...props}></Icon>
