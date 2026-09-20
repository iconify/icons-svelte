<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8fshfj-z.css';
import '../../css/n/nmroajm4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8fshfj-z"/><path clip-rule="evenodd" class="nmroajm4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toilet-paper-fill" {...props}></Icon>
