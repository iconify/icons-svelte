<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eps4tbc5w.css';
import '../../css/a/a18sp8bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eps4tbc5w"/><path class="a18sp8bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ultimate-certificate-manager-light" {...props}></Icon>
