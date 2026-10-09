<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6pf78o6u.css';
import '../../css/n/njbgecbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r6pf78o6u"/><path class="njbgecbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snowboard-20-bold" {...props}></Icon>
