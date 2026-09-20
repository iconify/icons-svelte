<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmpk6d91t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmpk6d91t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:waterdrops-outline" {...props}></Icon>
