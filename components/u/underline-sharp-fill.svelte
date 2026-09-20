<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl8fs8f5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl8fs8f5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:underline-sharp-fill" {...props}></Icon>
