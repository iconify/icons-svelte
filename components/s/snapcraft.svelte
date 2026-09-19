<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh_oxac7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lh_oxac7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:snapcraft" {...props}></Icon>
