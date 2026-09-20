<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd1geldrz.css';
import '../../css/o/oerqs_b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jd1geldrz"/><path class="oerqs_b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:users" {...props}></Icon>
