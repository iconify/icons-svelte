<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4-z48bjf.css';
import '../../css/h/hua-a9bjv.css';
import '../../css/n/nr0sg1b4q.css';
import '../../css/y/y85-cbbqp.css';
import '../../css/c/cd7p0qbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k4-z48bjf"/><path class="hua-a9bjv"/><path class="nr0sg1b4q"/><path class="y85-cbbqp"/><path class="cd7p0qbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:warning-strip" {...props}></Icon>
