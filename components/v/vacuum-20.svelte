<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9mgzabny.css';
import '../../css/p/p0dsglbia.css';
import '../../css/u/uj8cponlm.css';
import '../../css/u/u2ephhbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k9mgzabny"/><path class="p0dsglbia"/><path class="uj8cponlm"/><path class="u2ephhbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vacuum-20" {...props}></Icon>
