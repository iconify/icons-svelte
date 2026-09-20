<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8inqbcmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e8inqbcmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:script-1-solid" {...props}></Icon>
