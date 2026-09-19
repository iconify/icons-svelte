<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo2ehobow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mo2ehobow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:subdivision" {...props}></Icon>
