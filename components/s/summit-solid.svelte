<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4dvv9l9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4dvv9l9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:summit-solid" {...props}></Icon>
