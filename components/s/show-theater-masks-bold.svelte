<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2tyl-alg.css';
import '../../css/q/q6x95eb8d.css';
import '../../css/k/kt0rrab9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2tyl-alg"/><path class="q6x95eb8d"/><path class="kt0rrab9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:show-theater-masks-bold" {...props}></Icon>
