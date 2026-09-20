<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de4okpb9e.css';
import '../../css/x/x6suj9b7h.css';
import '../../css/r/rwj7e9bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de4okpb9e"/><path class="x6suj9b7h"/><path class="rwj7e9bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:uqc" {...props}></Icon>
