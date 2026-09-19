<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a27p9svzp.css';
import '../../css/u/u-dqumrtl.css';
import '../../css/k/kzia-bcxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a27p9svzp"/><path class="u-dqumrtl"/><path class="kzia-bcxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:study-read" {...props}></Icon>
