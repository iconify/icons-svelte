<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-oc9-2ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-oc9-2ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tornado" {...props}></Icon>
