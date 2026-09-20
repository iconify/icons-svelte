<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8eaj-gjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r8eaj-gjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:slack-logo-remix" {...props}></Icon>
