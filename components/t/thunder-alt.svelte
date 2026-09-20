<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez8bopsco.css';
import '../../css/i/io2oo-spz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ez8bopsco"/><path class="io2oo-spz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:thunder-alt" {...props}></Icon>
