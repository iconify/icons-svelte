<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw7y2gnxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw7y2gnxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zerotier" {...props}></Icon>
