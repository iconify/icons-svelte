<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agydu2b-r.css';
import '../../css/w/w26aucbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="agydu2b-r"/><path clip-rule="evenodd" class="w26aucbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stopwatch-solid" {...props}></Icon>
