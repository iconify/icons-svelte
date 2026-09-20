<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc_tocfpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mc_tocfpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shirt-fill" {...props}></Icon>
