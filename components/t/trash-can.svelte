<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrwt4tllx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jrwt4tllx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:trash-can" {...props}></Icon>
