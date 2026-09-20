<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4_v15wno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4_v15wno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-outline" {...props}></Icon>
