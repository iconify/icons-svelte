<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm2o0bbcb.css';
import '../../css/w/w5z9ayb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bm2o0bbcb"/><path class="w5z9ayb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vcore" {...props}></Icon>
