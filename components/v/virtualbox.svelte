<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow53i4btd.css';
import '../../css/j/jz3gn8btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow53i4btd"/><path class="jz3gn8btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:virtualbox" {...props}></Icon>
