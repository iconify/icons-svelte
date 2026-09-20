<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smn_1ccdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="smn_1ccdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:share-link-remix" {...props}></Icon>
