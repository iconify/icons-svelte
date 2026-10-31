<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzncnobio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzncnobio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-settings-corner-fill-round" {...props}></Icon>
