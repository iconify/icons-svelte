<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2n3zmxig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b2n3zmxig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:triangle-arrow-turn-down-left-large-remix" {...props}></Icon>
