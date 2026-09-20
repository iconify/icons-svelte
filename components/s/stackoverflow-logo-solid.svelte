<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik_fsylgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ik_fsylgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stackoverflow-logo-solid" {...props}></Icon>
