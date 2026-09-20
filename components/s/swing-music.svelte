<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6hwvs4-a.css';
import '../../css/h/heccpqbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6hwvs4-a"/><path class="heccpqbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swing-music" {...props}></Icon>
