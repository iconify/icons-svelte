<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ieikbdu.css';
import '../../css/y/ypqutt2oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i7ieikbdu"/><path class="ypqutt2oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tropical-storm-model-tracks" {...props}></Icon>
