<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0y-ep3tz.css';
import '../../css/p/ptk9sgbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0y-ep3tz"/><path clip-rule="evenodd" class="ptk9sgbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screen-share-outline" {...props}></Icon>
