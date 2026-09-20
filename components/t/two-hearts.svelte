<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai0cm1bnr.css';
import '../../css/z/z6ro75yjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ai0cm1bnr"/><path class="z6ro75yjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:two-hearts" {...props}></Icon>
