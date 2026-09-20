<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c11d1wxjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c11d1wxjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:toolbox-outline" {...props}></Icon>
