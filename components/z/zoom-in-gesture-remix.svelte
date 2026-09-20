<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndp3-e9tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ndp3-e9tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:zoom-in-gesture-remix" {...props}></Icon>
