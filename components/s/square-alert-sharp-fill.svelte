<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za0456b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="za0456b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-alert-sharp-fill" {...props}></Icon>
