<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy3z4m3dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy3z4m3dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:volume-min-filled" {...props}></Icon>
