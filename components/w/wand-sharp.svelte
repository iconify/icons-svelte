<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_l3fw_0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_l3fw_0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wand-sharp" {...props}></Icon>
