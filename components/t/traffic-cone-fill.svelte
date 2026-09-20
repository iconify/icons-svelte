<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts0eawbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts0eawbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:traffic-cone-fill" {...props}></Icon>
