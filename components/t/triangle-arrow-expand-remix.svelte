<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo5b263yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vo5b263yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:triangle-arrow-expand-remix" {...props}></Icon>
