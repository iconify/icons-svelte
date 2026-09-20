<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-2d2jb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-2d2jb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:safe-vault-remix" {...props}></Icon>
