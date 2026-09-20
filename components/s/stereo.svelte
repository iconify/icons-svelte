<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcq5rub-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcq5rub-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stereo" {...props}></Icon>
