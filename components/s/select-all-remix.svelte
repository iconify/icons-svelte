<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8vi7b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ba8vi7b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:select-all-remix" {...props}></Icon>
