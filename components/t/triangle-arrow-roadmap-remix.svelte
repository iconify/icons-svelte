<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6om9tvdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h6om9tvdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:triangle-arrow-roadmap-remix" {...props}></Icon>
