<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5szwaczv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o5szwaczv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ticket-1-remix" {...props}></Icon>
