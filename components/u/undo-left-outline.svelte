<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqdxw7bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqdxw7bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-outline" {...props}></Icon>
