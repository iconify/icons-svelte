<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siu7-7lbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="siu7-7lbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:workspace-desk" {...props}></Icon>
