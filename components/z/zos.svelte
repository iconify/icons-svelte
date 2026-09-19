<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szqt0p1li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="szqt0p1li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zos" {...props}></Icon>
