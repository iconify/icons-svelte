<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na20dj39s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="na20dj39s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:weights" {...props}></Icon>
