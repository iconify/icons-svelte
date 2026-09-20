<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdogh-bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdogh-bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tea-cup-solid" {...props}></Icon>
