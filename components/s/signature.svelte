<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz5lihbyw.css';
import '../../css/r/r-5a6yibn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz5lihbyw wm-k"/><path class="r-5a6yibn wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:signature" {...props}></Icon>
