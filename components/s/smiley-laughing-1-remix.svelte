<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sker2eb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sker2eb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:smiley-laughing-1-remix" {...props}></Icon>
