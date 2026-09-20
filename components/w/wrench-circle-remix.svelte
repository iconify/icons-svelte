<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7xiwkbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o7xiwkbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wrench-circle-remix" {...props}></Icon>
