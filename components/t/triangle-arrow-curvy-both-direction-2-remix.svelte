<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bysje_byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bysje_byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:triangle-arrow-curvy-both-direction-2-remix" {...props}></Icon>
