<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkgtonb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":192};
const content = `<path class="pkgtonb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sanity-dark" {...props}></Icon>
