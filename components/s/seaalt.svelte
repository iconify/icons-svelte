<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmdffacne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":960};
const content = `<path class="bmdffacne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:seaalt" {...props}></Icon>
