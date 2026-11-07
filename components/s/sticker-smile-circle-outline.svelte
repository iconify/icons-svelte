<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxg6ovbpq.css';
import '../../css/s/s4x--jb2i.css';
import '../../css/s/s9cx24dzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxg6ovbpq"/><path class="s4x--jb2i"/><path clip-rule="evenodd" class="s9cx24dzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-smile-circle-outline" {...props}></Icon>
