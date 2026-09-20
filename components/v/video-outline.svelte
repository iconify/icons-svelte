<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rij7cdc-q.css';
import '../../css/f/f7j85k9vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="rij7cdc-q"/><path class="f7j85k9vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:video-outline" {...props}></Icon>
