<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vayc-0b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vayc-0b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sword-attack-solid" {...props}></Icon>
