<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eikux7bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eikux7bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:voice-mail-solid" {...props}></Icon>
