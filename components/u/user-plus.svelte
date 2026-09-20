<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbeaf3bzp.css';
import '../../css/i/iik-bbx6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbeaf3bzp"/><path class="iik-bbx6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-plus" {...props}></Icon>
