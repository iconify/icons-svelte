<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnxmfkbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnxmfkbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sword-attack-remix" {...props}></Icon>
