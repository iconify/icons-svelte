<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx_3vpx0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx_3vpx0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-down-alt-1-fill" {...props}></Icon>
