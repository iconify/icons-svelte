<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbtjk6bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qbtjk6bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tune-adjust-volume" {...props}></Icon>
