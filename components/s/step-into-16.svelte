<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39j9zbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e39j9zbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:step-into-16" {...props}></Icon>
