<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhux28btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhux28btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tom-16" {...props}></Icon>
