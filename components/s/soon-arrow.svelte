<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddq_2tbpa.css';
import '../../css/a/avm-knshb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ddq_2tbpa"/><path class="avm-knshb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:soon-arrow" {...props}></Icon>
