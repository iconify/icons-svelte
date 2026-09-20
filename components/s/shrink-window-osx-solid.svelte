<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er7agu8tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er7agu8tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shrink-window-osx-solid" {...props}></Icon>
