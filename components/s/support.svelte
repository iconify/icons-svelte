<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/audo1xb5t.css';
import '../../css/v/vbbpf97ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="audo1xb5t"/><path class="vbbpf97ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:support" {...props}></Icon>
