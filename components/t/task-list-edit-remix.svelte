<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plh2b-bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="plh2b-bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:task-list-edit-remix" {...props}></Icon>
