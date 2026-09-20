<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcy6asx8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hcy6asx8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wizards-hat-with-star" {...props}></Icon>
