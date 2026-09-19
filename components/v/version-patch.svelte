<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3_ppud3s.css';
import '../../css/s/stheyzbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3_ppud3s"/><path class="stheyzbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:version-patch" {...props}></Icon>
