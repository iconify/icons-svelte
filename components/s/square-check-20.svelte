<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c961mpvnt.css';
import '../../css/f/f_m6gmbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c961mpvnt"/><path class="f_m6gmbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-check-20" {...props}></Icon>
