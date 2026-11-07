<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r34ssebvg.css';
import '../../css/k/kroiddczm.css';
import '../../css/m/mmoj81bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r34ssebvg"/><path class="kroiddczm"/><path class="mmoj81bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-bolt-bold" {...props}></Icon>
