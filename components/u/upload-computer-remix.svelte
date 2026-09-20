<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgwml-q3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgwml-q3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:upload-computer-remix" {...props}></Icon>
