<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqaetjboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rqaetjboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tamtam-16" {...props}></Icon>
