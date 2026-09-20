<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84xo7bjy.css';
import '../../css/o/okm7grcet.css';
import '../../css/o/oeuv6sbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w84xo7bjy"/><path class="okm7grcet"/><path class="oeuv6sbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube-watcher" {...props}></Icon>
