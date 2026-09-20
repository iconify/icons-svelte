<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz31dcpqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz31dcpqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ship-solid" {...props}></Icon>
