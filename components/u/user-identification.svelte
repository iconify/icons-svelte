<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2abs1bhy.css';
import '../../css/v/v23tyc59y.css';
import '../../css/f/fhiircb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t2abs1bhy"/><circle class="v23tyc59y"/><path class="fhiircb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-identification" {...props}></Icon>
