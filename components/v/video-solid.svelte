<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x99brs7fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x99brs7fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:video-solid" {...props}></Icon>
