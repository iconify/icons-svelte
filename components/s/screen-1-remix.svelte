<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1_i63b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f1_i63b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:screen-1-remix" {...props}></Icon>
