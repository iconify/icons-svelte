<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4a_jpbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b4a_jpbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wine-remix" {...props}></Icon>
