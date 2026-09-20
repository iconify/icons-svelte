<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q570a2b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q570a2b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:spotify-logo-remix" {...props}></Icon>
