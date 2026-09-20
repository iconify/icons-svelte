<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9bwdn8yu.css';
import '../../css/u/u06779bpm.css';
import '../../css/c/cn03m5p3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k9bwdn8yu"/><path class="u06779bpm"/><path class="cn03m5p3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:tooth" {...props}></Icon>
