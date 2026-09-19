<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsu2q7bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bsu2q7bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:square-medium-outline" {...props}></Icon>
