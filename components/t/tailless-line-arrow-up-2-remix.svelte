<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb800tpmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vb800tpmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tailless-line-arrow-up-2-remix" {...props}></Icon>
