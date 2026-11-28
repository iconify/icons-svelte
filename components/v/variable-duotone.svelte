<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx6sh1ufv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qx6sh1ufv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:variable-duotone" {...props}></Icon>
