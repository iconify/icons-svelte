<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5iqyiiyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i5iqyiiyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:toilet" {...props}></Icon>
