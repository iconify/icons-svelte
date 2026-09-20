<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lns7h3qht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lns7h3qht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-outline" {...props}></Icon>
