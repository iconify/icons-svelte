<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3nrppbry.css';
import '../../css/q/q7w59bb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="x3nrppbry"/><path class="q7w59bb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:sweden" {...props}></Icon>
