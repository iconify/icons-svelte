<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq3f9327i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yq3f9327i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wifi-signal-full-remix" {...props}></Icon>
