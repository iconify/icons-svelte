<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnwldwb2b.css';
import '../../css/n/nuq19qbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnwldwb2b"/><path clip-rule="evenodd" class="nuq19qbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:share-duotone" {...props}></Icon>
