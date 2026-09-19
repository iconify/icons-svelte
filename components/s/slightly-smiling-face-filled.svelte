<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr6m2nb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tr6m2nb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slightly-smiling-face-filled" {...props}></Icon>
