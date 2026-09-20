<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kii1hnb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kii1hnb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:shamisen-16" {...props}></Icon>
