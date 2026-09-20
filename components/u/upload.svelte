<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxqgy5otv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxqgy5otv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:upload" {...props}></Icon>
