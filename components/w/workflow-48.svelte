<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntf6lmu1o.css';
import '../../css/z/zo2elrbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ntf6lmu1o"/><path class="zo2elrbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:workflow-48" {...props}></Icon>
