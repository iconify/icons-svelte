<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6xb5abaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h6xb5abaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sunset" {...props}></Icon>
