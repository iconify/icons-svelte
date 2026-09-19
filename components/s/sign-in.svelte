<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/ed7fvnb1p.css';
import '../../css/m/m6xzm-jkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<g class="n1lsf0bnc"><path class="ed7fvnb1p"/><path class="m6xzm-jkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sign-in" {...props}></Icon>
