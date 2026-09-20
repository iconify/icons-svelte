<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp2kr3bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fp2kr3bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:two-finger-drag-hotizontal-remix" {...props}></Icon>
