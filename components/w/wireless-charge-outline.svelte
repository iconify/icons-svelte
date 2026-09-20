<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf3k0wf1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf3k0wf1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wireless-charge-outline" {...props}></Icon>
