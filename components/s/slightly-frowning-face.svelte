<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy37ombvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oy37ombvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slightly-frowning-face" {...props}></Icon>
