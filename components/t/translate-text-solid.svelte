<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekyi5ob7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekyi5ob7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:translate-text-solid" {...props}></Icon>
