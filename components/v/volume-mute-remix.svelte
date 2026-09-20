<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1m46ir4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l1m46ir4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:volume-mute-remix" {...props}></Icon>
