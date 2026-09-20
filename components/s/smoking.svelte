<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_5w4bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c3_5w4bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:smoking" {...props}></Icon>
