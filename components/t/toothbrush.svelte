<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iormuebre.css';
import '../../css/f/fzppklb-k.css';
import '../../css/p/p0rwbubiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="iormuebre"/><path class="fzppklb-k"/><path class="p0rwbubiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:toothbrush" {...props}></Icon>
