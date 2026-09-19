<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3w7_bbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x3w7_bbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:squint-smiling-face-small" {...props}></Icon>
