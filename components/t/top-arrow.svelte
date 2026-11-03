<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymz4q6yty.css';
import '../../css/k/ksfjye7xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ymz4q6yty"/><path class="ksfjye7xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:top-arrow" {...props}></Icon>
