<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjh33ebuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjh33ebuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:window-fill" {...props}></Icon>
