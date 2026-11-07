<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz__5zbvx.css';
import '../../css/j/jflyr3bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bz__5zbvx"/><path class="jflyr3bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ufo-bold" {...props}></Icon>
