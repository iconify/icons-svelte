<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s26-ekb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s26-ekb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sparkles-filled" {...props}></Icon>
