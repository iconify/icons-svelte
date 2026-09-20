<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2-qpdbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w2-qpdbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:toilet-man-remix" {...props}></Icon>
