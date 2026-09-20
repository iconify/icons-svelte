<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev_271blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ev_271blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tool-box-remix" {...props}></Icon>
