<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshe_di8n.css';
import '../../css/b/bxbtl1b7w.css';
import '../../css/i/ii51yubpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="bxbtl1b7w"/><path class="ii51yubpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:smiley" {...props}></Icon>
