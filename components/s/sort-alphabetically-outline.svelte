<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in77xtbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in77xtbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-alphabetically-outline" {...props}></Icon>
