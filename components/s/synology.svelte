<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0bvlpdn.css';
import '../../css/t/tdr-0yasd.css';
import '../../css/s/s-edpzbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak0bvlpdn"/><path class="tdr-0yasd"/><path class="s-edpzbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synology" {...props}></Icon>
