<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1o--8zmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f1o--8zmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:virtual-reality-remix" {...props}></Icon>
