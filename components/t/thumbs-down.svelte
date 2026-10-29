<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kio4hsg7t.css';
import '../../css/n/nljnanbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kio4hsg7t wm-a"/><path class="nljnanbsb wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:thumbs-down" {...props}></Icon>
