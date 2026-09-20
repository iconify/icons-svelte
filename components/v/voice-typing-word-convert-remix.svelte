<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wor_cd2ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wor_cd2ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:voice-typing-word-convert-remix" {...props}></Icon>
