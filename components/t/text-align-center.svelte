<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s31d6pb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s31d6pb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:text-align-center" {...props}></Icon>
