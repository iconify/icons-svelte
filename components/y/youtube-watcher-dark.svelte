<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szxsx5wma.css';
import '../../css/z/zf9qombco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="szxsx5wma"/><path class="zf9qombco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube-watcher-dark" {...props}></Icon>
