<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_bpyn97l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v_bpyn97l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-remove-subtract-remix" {...props}></Icon>
