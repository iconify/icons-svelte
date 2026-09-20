<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh64f7b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sh64f7b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sign-at-remix" {...props}></Icon>
