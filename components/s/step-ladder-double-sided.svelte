<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo2gw7byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vo2gw7byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:step-ladder-double-sided" {...props}></Icon>
