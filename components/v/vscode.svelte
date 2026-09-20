<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shmltxb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="shmltxb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vscode" {...props}></Icon>
